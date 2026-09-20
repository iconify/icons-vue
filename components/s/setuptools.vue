<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akuk0wb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akuk0wb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:setuptools" /></template>
