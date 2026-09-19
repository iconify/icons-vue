<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbst9ofjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbst9ofjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:touch-02" /></template>
