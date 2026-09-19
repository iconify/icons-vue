<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5nansb4m.css';
import '../../css/g/ghanqywqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q5nansb4m"/><rect class="ghanqywqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:smartcard-filled" /></template>
