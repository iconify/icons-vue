<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-scspq5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:organic" /></template>
<style>
.x-scspq5p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.108 15.766q.852-2.082-.379-3.766q1.231-1.684.379-3.766q-.853-2.087-2.92-2.422q-.335-2.067-2.422-2.92q-2.082-.852-3.766.379q-1.684-1.231-3.766-.379q-2.087.853-2.422 2.92q-2.067.335-2.92 2.422q-.852 2.082.379 3.766q-1.231 1.684-.379 3.766q.853 2.087 2.92 2.422q.335 2.067 2.422 2.92q2.082.852 3.766-.379q1.684 1.231 3.766.379q2.087-.853 2.422-2.92q2.067-.335 2.92-2.422M15.25 8q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146Q16 16 8.75 16q-.149 0-.287-.057t-.243-.163q-.106-.105-.163-.243T8 15.25Q8 8 15.25 8");
}

</style>
