<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylnr7y52n.css';
import '../../css/h/hs-lm0b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<circle class="ylnr7y52n"/><path class="hs-lm0b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:play-26" /></template>
