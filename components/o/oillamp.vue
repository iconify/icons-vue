<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8z9q-b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="b8z9q-b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:oillamp" /></template>
