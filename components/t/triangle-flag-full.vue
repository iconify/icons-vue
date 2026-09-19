<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li8dkqbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li8dkqbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:triangle-flag-full" /></template>
