<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g80a0ivmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g80a0ivmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:turntable" /></template>
