<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkqtqp8yr.css';
import '../../css/u/uw_8mqbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkqtqp8yr"/><path clip-rule="evenodd" class="uw_8mqbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:target-fill" /></template>
