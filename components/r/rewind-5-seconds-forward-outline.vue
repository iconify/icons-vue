<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyxqbob-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kyxqbob-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-5-seconds-forward-outline" /></template>
