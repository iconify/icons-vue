<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5e6hntgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5e6hntgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-star-sharp" /></template>
