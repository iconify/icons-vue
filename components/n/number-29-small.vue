<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7jt3bbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7jt3bbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-29-small" /></template>
