<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhq33bcqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhq33bcqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:transfer-long-top" /></template>
