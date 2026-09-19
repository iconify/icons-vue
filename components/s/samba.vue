<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofd9gvb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofd9gvb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:samba" /></template>
