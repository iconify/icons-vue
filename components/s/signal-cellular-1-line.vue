<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq1uwrb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq1uwrb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-cellular-1-line" /></template>
