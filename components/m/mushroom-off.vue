<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apinnx7pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apinnx7pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mushroom-off" /></template>
