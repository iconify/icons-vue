<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2dkisrbn.css';
import '../../css/i/i483i_kue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2dkisrbn"/><path class="i483i_kue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:phone-incoming-fill" /></template>
