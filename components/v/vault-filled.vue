<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an3z_3bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an3z_3bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:vault-filled" /></template>
