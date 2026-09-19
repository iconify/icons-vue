<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edvji8e5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="edvji8e5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:relationship-bounds" /></template>
