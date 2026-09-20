<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o19vw7hlu.css';
import '../../css/a/a2s72obzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o19vw7hlu"/><path clip-rule="evenodd" class="a2s72obzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:undeploy" /></template>
