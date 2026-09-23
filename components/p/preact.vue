<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_hp_0bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_hp_0bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:preact" /></template>
