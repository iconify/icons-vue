<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2iw6y11v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w2iw6y11v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:outdent-solid" /></template>
