<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu5zzebua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu5zzebua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:megaphone-light" /></template>
