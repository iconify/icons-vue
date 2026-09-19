<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9av61y3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9av61y3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-protection" /></template>
