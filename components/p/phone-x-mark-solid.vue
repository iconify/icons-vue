<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo4lcqbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xo4lcqbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:phone-x-mark-solid" /></template>
