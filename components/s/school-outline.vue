<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s12qakbkj.css';
import '../../css/q/q6hvgntet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s12qakbkj"/><path class="q6hvgntet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:school-outline" /></template>
