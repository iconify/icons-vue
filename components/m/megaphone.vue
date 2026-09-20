<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny0sn3mdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ny0sn3mdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:megaphone" /></template>
