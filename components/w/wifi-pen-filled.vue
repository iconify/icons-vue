<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjocleb1j.css';
import '../../css/b/b54fotqqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjocleb1j"/><path class="b54fotqqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:wifi-pen-filled" /></template>
