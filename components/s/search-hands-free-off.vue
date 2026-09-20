<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-53p7byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-53p7byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:search-hands-free-off" /></template>
