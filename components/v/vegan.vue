<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9n9rckuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9n9rckuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:vegan" /></template>
