<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lloebebob.css';
import '../../css/g/gwm-eyb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lloebebob"/><path class="gwm-eyb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-alt-arrow-up-bold-duotone" /></template>
