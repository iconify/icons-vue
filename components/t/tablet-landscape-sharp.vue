<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz4t6jbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zz4t6jbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:tablet-landscape-sharp" /></template>
