<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_js4bbia.css';
import '../../css/d/d47xi2b9o.css';
import '../../css/b/be97_nbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j_js4bbia"/><path class="d47xi2b9o"/><path class="be97_nbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:peso" /></template>
