<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow15xdb1e.css';
import '../../css/e/eeg6scbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow15xdb1e"/><path class="eeg6scbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-check-duotone" /></template>
