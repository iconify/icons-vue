<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f99tpmb6q.css';
import '../../css/e/ew-5e-iwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f99tpmb6q"/><path class="ew-5e-iwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-minus-duotone" /></template>
