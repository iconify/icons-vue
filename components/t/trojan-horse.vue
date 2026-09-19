<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5hp6omba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o5hp6omba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trojan-horse" /></template>
