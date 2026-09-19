<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcmybyb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcmybyb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:microsoft-admin" /></template>
