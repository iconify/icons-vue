<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_bkjqbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:podcast-mic-off" /></template>
<style>
.m_bkjqbys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.741 4.723q.048-.122.105-.24t.122-.231q.065-.114.139-.222t.156-.211q.081-.102.17-.199q.089-.096.185-.185t.199-.171t.21-.155q.109-.074.222-.14q.114-.065.232-.122t.24-.105t.247-.086q.125-.039.253-.068t.257-.049q.13-.019.26-.029q.131-.01.262-.01q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333t.05.34T15.5 6v4q0 .669-.247 1.291M5.5 10.5q0 .16.008.319t.023.318q.016.159.039.317q.024.158.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297t.129.292t.144.285q.075.141.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209t.252.196t.261.184q.132.088.269.17t.278.157q.141.076.285.144t.292.129t.297.115t.303.1t.308.085t.311.07t.314.055t.317.039t.318.023T12 17q.501 0 .995-.077m4.684-3.26q.404-.725.612-1.529q.209-.804.209-1.634M12 17v4.5m-3.5 0h7m-12-18l17 17");
}

</style>
