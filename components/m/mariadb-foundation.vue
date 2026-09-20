<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kknkui68e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kknkui68e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mariadb-foundation" /></template>
