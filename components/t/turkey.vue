<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdftbpbaj.css';
import '../../css/m/m26ewvbtd.css';
import '../../css/g/gw6wfjnqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="wdftbpbaj"/><path class="m26ewvbtd"/><path class="gw6wfjnqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:turkey" /></template>
