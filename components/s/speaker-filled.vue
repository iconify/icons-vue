<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2j9pvdbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2j9pvdbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:speaker-filled" /></template>
