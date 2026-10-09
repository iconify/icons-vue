<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-ilkisjd.css';
import '../../css/n/n-b_rl70t.css';
import '../../css/s/s8zhrbi_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f-ilkisjd"/><path class="n-b_rl70t"/><path class="s8zhrbi_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sync-20" /></template>
