<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkyej1bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkyej1bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-arrow-up-filled" /></template>
