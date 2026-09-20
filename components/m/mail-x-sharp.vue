<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfwxa0bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfwxa0bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-x-sharp" /></template>
