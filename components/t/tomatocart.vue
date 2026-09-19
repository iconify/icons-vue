<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf_wirsww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tf_wirsww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tomatocart" /></template>
