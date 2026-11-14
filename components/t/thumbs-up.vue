<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecpwv1b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecpwv1b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:thumbs-up" /></template>
