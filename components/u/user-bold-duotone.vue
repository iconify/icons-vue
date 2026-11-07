<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0nhpsynn.css';
import '../../css/b/bxpukbbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="f0nhpsynn"/><path class="bxpukbbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-bold-duotone" /></template>
