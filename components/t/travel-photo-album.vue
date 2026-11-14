<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwe3-xbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:travel-photo-album" /></template>
<style>
.kwe3-xbdc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 3.75h9q1.76 0 3.005 1.245T20.75 8v8q0 .775-.241 1.449l-.011-.01l-4.5-4q-.049-.043-.105-.078q-.056-.034-.117-.059t-.126-.037t-.131-.015q-.065-.001-.131.008q-.065.01-.127.031t-.12.053t-.11.072l-1.975 1.581L9.53 11.47q-.105-.106-.243-.163T9 11.25t-.287.057t-.243.163l-5 5q-.108.107-.165.248Q3.25 16.37 3.25 16V8q0-1.76 1.245-3.005T7.5 3.75M3.548 17.598q.311.771.947 1.407Q5.74 20.25 7.5 20.25h9q1.76 0 3.005-1.245q.142-.142.268-.29q-.152-.049-.271-.154l-4.027-3.58l-2.006 1.605q-.054.043-.115.075q-.06.032-.125.053q-.066.021-.134.03t-.136.005t-.136-.02q-.066-.016-.129-.044t-.119-.067t-.105-.088L9 13.061L4.53 17.53q-.105.106-.243.163T4 17.75q-.122 0-.239-.039t-.213-.113M15 7.25q-2.25 0-2.25 2.25T15 11.75t2.25-2.25T15 7.25");
}

</style>
