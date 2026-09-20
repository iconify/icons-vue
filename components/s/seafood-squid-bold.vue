<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bym9qzlxy.css';
import '../../css/y/yzb5i2o5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bym9qzlxy"/><path class="yzb5i2o5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:seafood-squid-bold" /></template>
