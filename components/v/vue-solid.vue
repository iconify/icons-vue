<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3_m4jflw.css';
import '../../css/a/aaznl0b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c3_m4jflw"/><path class="aaznl0b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:vue-solid" /></template>
