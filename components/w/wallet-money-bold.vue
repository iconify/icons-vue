<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b--gob6xd.css';
import '../../css/s/siuvu-jzd.css';
import '../../css/r/r377frbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b--gob6xd"/><path clip-rule="evenodd" class="siuvu-jzd"/><path class="r377frbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wallet-money-bold" /></template>
