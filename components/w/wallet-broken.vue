<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/acmhcgbix.css';
import '../../css/i/ihob04h8r.css';
import '../../css/t/t2jvb6bpe.css';
import '../../css/m/m1-6nzrja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="acmhcgbix"/><path class="ihob04h8r"/><path class="t2jvb6bpe"/><path class="m1-6nzrja"/><path class="t2jvb6bpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wallet-broken" /></template>
