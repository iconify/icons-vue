<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pamsoyntu.css';
import '../../css/f/ftg34obra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pamsoyntu"/><path class="ftg34obra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:message-writing" /></template>
