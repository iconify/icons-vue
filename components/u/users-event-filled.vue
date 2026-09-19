<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrezf1u2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xrezf1u2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:users-event-filled" /></template>
