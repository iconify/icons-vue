<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4zprc1uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4zprc1uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-x-filled" /></template>
