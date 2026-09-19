<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1l_6cc3h.css';
import '../../css/o/oxijutbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="e1l_6cc3h"/><path class="oxijutbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:pulse" /></template>
