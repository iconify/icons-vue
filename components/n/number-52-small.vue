<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtdtjootm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtdtjootm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-52-small" /></template>
