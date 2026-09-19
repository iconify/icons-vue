<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb078absx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bb078absx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stakes-fence" /></template>
