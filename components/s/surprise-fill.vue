<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7nf_hb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7nf_hb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:surprise-fill" /></template>
