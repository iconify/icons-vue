<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h93zme_zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h93zme_zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:traffic-barrier-filled" /></template>
