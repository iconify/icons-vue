<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/g/gz47tp26q.css';
import '../../css/e/e31w36bfn.css';
import '../../css/q/q98kknj2b.css';
import '../../css/z/zfvqimbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="gz47tp26q wm-shadow"/><path class="e31w36bfn wm-shadow"/><path class="q98kknj2b"/><path class="zfvqimbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:rectangle-ellipsis" /></template>
