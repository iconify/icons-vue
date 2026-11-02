<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1sk0j9gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1sk0j9gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:triumphal-arch-fill" /></template>
