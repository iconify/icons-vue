<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbj016bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbj016bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-trending-up-fill" /></template>
