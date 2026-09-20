<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydc7yznbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydc7yznbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-outgoing-sharp" /></template>
