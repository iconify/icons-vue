<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr-9cvk0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr-9cvk0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:table-lamp-01" /></template>
