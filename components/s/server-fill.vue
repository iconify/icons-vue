<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b66k_dq-g.css';
import '../../css/k/k-jty3jzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b66k_dq-g"/><path clip-rule="evenodd" class="k-jty3jzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:server-fill" /></template>
