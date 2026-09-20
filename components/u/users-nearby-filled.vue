<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/ch1ctkp8j.css';
import '../../css/l/lb3khzbez.css';
import '../../css/i/i9o8s-0wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ch1ctkp8j"/><path class="lb3khzbez"/><path class="i9o8s-0wl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:users-nearby-filled" /></template>
