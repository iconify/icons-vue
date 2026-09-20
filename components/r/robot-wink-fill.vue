<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9znpqbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9znpqbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:robot-wink-fill" /></template>
