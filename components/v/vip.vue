<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzlv41b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzlv41b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:vip" /></template>
