<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpgd2ibzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gpgd2ibzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:speaker-zzz" /></template>
