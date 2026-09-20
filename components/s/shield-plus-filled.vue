<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvb5if0vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvb5if0vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shield-plus-filled" /></template>
