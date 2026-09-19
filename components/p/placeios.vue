<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz6jcob4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xz6jcob4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:placeios" /></template>
