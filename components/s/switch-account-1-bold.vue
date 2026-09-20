<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw245nb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jw245nb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:switch-account-1-bold" /></template>
