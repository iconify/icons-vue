<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug90t0lcu.css';
import '../../css/v/v783iab8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug90t0lcu"/><circle class="v783iab8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:volume" /></template>
