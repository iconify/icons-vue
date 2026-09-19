<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgbnlkb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lgbnlkb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:trophy" /></template>
