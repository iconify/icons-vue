<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahu42d9pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahu42d9pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:person-multiple" /></template>
