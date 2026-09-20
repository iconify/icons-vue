<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6nd3rb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6nd3rb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mug-filled" /></template>
