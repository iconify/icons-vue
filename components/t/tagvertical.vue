<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxxo1bbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":770,"height":1024};
const content = `<path class="oxxo1bbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tagvertical" /></template>
