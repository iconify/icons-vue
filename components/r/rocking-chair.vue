<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkwno1bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkwno1bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rocking-chair" /></template>
