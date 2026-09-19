<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp7hdwqxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp7hdwqxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:widget" /></template>
