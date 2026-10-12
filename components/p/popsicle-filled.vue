<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/big4id24i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="big4id24i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:popsicle-filled" /></template>
