<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tl42b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="y9tl42b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:male" /></template>
