<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghb64morl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghb64morl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-14-small" /></template>
