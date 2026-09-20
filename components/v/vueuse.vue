<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg17mhb7c.css';
import '../../css/q/qyzx5zbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":277};
const content = `<path class="bg17mhb7c"/><path class="qyzx5zbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vueuse" /></template>
