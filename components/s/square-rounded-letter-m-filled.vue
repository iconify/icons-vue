<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlp6wvbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlp6wvbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-m-filled" /></template>
