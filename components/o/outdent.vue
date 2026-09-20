<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylue4nulp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylue4nulp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:outdent" /></template>
