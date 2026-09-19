<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmv3c7gqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmv3c7gqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:t-shirt" /></template>
