<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6jc4kd1z.css';
import '../../css/b/bikjexb7g.css';
import '../../css/j/j_8h5jbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q6jc4kd1z"/><path class="bikjexb7g"/><path class="j_8h5jbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:margin" /></template>
