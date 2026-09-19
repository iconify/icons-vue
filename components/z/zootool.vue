<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt3-jpbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":312,"height":488};
const content = `<path class="bt3-jpbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:zootool" /></template>
