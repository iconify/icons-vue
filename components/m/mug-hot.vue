<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bskjuj5fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bskjuj5fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mug-hot" /></template>
