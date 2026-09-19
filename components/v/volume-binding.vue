<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6dafjbul.css';
import '../../css/w/wrevi32si.css';
import '../../css/b/btx35_8hm.css';
import '../../css/a/ah1zjobhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6dafjbul"/><circle class="wrevi32si"/><path class="btx35_8hm"/><path class="ah1zjobhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:volume-binding" /></template>
