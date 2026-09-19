<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apyavpbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apyavpbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:swimming-pool-filled" /></template>
