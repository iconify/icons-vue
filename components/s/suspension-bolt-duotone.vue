<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iql384b-f.css';
import '../../css/s/s_rsn3foo.css';
import '../../css/k/kn9hn5b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iql384b-f"/><path class="s_rsn3foo"/><path clip-rule="evenodd" class="kn9hn5b8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:suspension-bolt-duotone" /></template>
