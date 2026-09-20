<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz_le0wpd.css';
import '../../css/e/ewl5wjk4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz_le0wpd"/><path class="ewl5wjk4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:notification-bell-pending-fill" /></template>
