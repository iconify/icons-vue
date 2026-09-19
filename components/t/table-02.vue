<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2t02b29a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2t02b29a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:table-02" /></template>
