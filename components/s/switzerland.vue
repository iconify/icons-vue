<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnnw6covj.css';
import '../../css/r/rjp1fpm9e.css';
import '../../css/s/snp287xku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qnnw6covj"/><path class="rjp1fpm9e"/><path class="snp287xku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:switzerland" /></template>
