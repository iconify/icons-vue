<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl4m8djlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl4m8djlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:user-add" /></template>
