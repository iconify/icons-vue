<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1tq20b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="o1tq20b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:switch-camera" /></template>
