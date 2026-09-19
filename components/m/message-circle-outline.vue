<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dftf9rvck.css';
import '../../css/a/a11bti4rf.css';
import '../../css/s/stjv0pdcv.css';
import '../../css/p/pmr9h6bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="dftf9rvck"/><circle class="a11bti4rf"/><circle class="stjv0pdcv"/><path class="pmr9h6bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:message-circle-outline" /></template>
