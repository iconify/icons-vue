<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3jobgg0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3jobgg0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sort-9-0" /></template>
