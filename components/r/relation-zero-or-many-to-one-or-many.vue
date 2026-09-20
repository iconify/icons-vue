<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcj1yhvjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcj1yhvjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-zero-or-many-to-one-or-many" /></template>
