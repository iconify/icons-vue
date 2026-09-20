<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my_0eb8dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my_0eb8dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:school-filled" /></template>
