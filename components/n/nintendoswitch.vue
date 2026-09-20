<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9qvvjnrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9qvvjnrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nintendoswitch" /></template>
