<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_c3lsbki.css';
import '../../css/g/gs5s95byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x_c3lsbki"/><path class="gs5s95byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:python-solid" /></template>
