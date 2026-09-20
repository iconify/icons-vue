<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7a5ug5iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:privacy-tip-outline-rounded" /></template>
<style>
.s7a5ug5iw {
  fill: currentColor;
  d: path("M12.357 16.088q.143-.144.143-.357v-4.654q0-.213-.143-.357T12 10.577t-.357.143t-.143.357v4.654q0 .213.143.357t.357.143t.357-.144m.077-7.269q.182-.181.182-.433t-.182-.434T12 7.769t-.434.182t-.182.434t.182.433T12 9t.434-.182m-.72 12q-.15-.026-.281-.076q-2.952-1.125-4.692-3.816T5 11.1V6.817q0-.51.295-.923t.755-.6l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.46.187.755.6t.295.923V11.1q0 3.135-1.74 5.826t-4.693 3.816q-.13.05-.28.075t-.287.025t-.287-.025M12 19.9q2.6-.825 4.3-3.3t1.7-5.5V6.798q0-.192-.106-.346q-.105-.154-.298-.23l-5.384-2q-.096-.04-.212-.04t-.212.04l-5.384 2q-.193.076-.298.23Q6 6.606 6 6.798V11.1q0 3.025 1.7 5.5t4.3 3.3m0-7.861");
}

</style>
