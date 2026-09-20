<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgdh1dbhf.css';
import '../../css/p/pds7e2php.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sgdh1dbhf"/><path class="pds7e2php"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plain-2-bold-duotone" /></template>
