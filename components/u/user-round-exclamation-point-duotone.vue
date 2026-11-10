<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zlcvyh7fb.css';
import '../../css/t/ty-zitbel.css';
import '../../css/i/ig-kolbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zlcvyh7fb"/><path class="ty-zitbel"/><path class="ig-kolbmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-exclamation-point-duotone" /></template>
