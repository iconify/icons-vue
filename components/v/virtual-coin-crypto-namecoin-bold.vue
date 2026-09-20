<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7poolbui.css';
import '../../css/q/qc9ri3n6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7poolbui"/><path class="qc9ri3n6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:virtual-coin-crypto-namecoin-bold" /></template>
