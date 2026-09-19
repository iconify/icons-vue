<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwudjlbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1001,"height":1000};
const content = `<path class="qwudjlbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:spin4" /></template>
