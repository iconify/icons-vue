<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb5mbg0ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb5mbg0ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-x-sharp" /></template>
