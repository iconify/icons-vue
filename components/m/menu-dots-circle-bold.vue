<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta0hcqbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ta0hcqbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:menu-dots-circle-bold" /></template>
