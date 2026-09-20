<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_-d-b5tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_-d-b5tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tinkercad" /></template>
